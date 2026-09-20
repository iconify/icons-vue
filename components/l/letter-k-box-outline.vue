<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg4qlh80c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg4qlh80c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-k-box-outline" /></template>
