<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5a7bnb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5a7bnb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-codepen" /></template>
