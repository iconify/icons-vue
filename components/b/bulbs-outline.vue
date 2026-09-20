<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eleh99bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eleh99bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bulbs-outline" /></template>
