<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yalszgd8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yalszgd8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:credit-card-arrow-right" /></template>
