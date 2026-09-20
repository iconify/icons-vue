<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xps1z-igg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xps1z-igg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:icons" /></template>
