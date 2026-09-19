<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5_886_2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c5_886_2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:layers-alt-fill" /></template>
