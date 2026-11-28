<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn1-m4b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn1-m4b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:magnet" /></template>
