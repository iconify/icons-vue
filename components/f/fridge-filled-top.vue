<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xubqcf4ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xubqcf4ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-filled-top" /></template>
