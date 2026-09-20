<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfas3bcyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lfas3bcyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cart-full" /></template>
