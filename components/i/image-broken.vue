<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfv9sopxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yfv9sopxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-broken" /></template>
