<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb-3c9yjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-3c9yjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cart-x" /></template>
