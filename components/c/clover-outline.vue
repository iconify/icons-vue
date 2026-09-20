<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2-e3ebfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2-e3ebfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clover-outline" /></template>
