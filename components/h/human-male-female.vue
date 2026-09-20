<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sux_9dg_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sux_9dg_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-male-female" /></template>
