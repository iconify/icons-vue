<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9x4_cb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="d9x4_cb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:jug-detergent" /></template>
