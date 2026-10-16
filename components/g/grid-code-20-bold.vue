<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny-w6qbwa.css';
import '../../css/i/iw77clbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ny-w6qbwa"/><path class="iw77clbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-code-20-bold" /></template>
