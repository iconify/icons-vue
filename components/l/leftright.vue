<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r97h_xb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r97h_xb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:leftright" /></template>
