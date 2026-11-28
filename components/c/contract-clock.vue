<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlib3xb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlib3xb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contract-clock" /></template>
