<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgc7ehb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgc7ehb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bluetooth" /></template>
