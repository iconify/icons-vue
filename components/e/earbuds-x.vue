<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4w5r3bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4w5r3bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:earbuds-x" /></template>
