<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_yz11bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_yz11bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:games" /></template>
