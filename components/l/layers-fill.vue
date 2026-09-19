<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck5r02b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ck5r02b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:layers-fill" /></template>
