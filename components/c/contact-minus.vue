<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg5x5g5zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg5x5g5zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:contact-minus" /></template>
