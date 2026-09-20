<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upzgenbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upzgenbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-arrow-info" /></template>
