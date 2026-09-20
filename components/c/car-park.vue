<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p03tihhfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p03tihhfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-park" /></template>
