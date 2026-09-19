<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl3ostbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zl3ostbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-rtl-stroke-12" /></template>
