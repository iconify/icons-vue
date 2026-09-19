<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlx2ab_yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="zlx2ab_yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bell-o" /></template>
