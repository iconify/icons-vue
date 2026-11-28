<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whyykqbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="whyykqbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bell-dot" /></template>
