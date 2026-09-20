<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by2od_5uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="by2od_5uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:4chan" /></template>
