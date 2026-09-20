<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqr6emsqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqr6emsqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:link-variant-minus" /></template>
