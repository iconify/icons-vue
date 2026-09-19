<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-1rciyzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x-1rciyzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:link-circle" /></template>
