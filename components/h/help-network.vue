<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvxbf4bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvxbf4bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:help-network" /></template>
