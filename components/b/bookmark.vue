<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr9y6zxld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zr9y6zxld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:bookmark" /></template>
