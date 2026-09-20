<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5qo3wbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5qo3wbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-minus-outline" /></template>
