<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mii7rxkxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mii7rxkxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-6-round" /></template>
