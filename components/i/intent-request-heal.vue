<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znaj4nbie.css';
import '../../css/u/uc_6-wbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="znaj4nbie"/><path class="uc_6-wbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intent-request-heal" /></template>
