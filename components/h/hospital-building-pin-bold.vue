<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7r-vt5ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7r-vt5ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:hospital-building-pin-bold" /></template>
