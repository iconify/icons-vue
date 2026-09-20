<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlzgxp-_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nlzgxp-_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-disambiguation-ltr" /></template>
