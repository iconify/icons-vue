<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i72reac_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i72reac_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hook-off" /></template>
