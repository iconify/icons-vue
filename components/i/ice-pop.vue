<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf6-64bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gf6-64bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ice-pop" /></template>
