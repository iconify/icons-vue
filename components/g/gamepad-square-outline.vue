<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhed42bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhed42bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-square-outline" /></template>
