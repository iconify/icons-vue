<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxcxpybik.css';
import '../../css/l/l1u6ybcci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxcxpybik"/><path class="l1u6ybcci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-flip" /></template>
