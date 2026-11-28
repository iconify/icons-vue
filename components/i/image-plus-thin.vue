<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzz7xk7cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uzz7xk7cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:image-plus-thin" /></template>
