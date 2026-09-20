<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfjju0lxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfjju0lxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-saloon" /></template>
