<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m-1d2wutd.css';
import '../../css/a/amc1qtlun.css';
import '../../css/n/nvbta5b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="m-1d2wutd"/><path class="amc1qtlun"/><path class="nvbta5b-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:ant" /></template>
