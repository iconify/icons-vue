<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj8mcob3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj8mcob3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bluetooth-sharp-fill" /></template>
