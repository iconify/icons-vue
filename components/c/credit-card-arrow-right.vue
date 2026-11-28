<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeogqjy-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeogqjy-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:credit-card-arrow-right" /></template>
