<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xae-8gbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xae-8gbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:box-open-check" /></template>
