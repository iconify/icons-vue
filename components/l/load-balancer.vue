<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im4cxtbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="im4cxtbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:load-balancer" /></template>
