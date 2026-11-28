<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a80-k7bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a80-k7bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cap" /></template>
