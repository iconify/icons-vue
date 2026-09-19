<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_xuckbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="k_xuckbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cloudupload" /></template>
