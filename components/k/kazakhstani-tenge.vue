<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkjmr59pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkjmr59pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kazakhstani-tenge" /></template>
