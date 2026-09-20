<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl0y-5bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rl0y-5bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:data-transfer-upload" /></template>
