<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avu3_us6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="avu3_us6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:badge" /></template>
