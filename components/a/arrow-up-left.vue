<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td599z-9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td599z-9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-left" /></template>
