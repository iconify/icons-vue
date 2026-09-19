<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf7od_ncm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gf7od_ncm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:image-flip-vertical" /></template>
