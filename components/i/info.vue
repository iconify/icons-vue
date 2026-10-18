<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi2r89w-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi2r89w-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:info" /></template>
