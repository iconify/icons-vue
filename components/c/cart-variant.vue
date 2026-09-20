<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6j704wpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6j704wpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cart-variant" /></template>
