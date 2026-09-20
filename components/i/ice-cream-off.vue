<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_0hr8blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_0hr8blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ice-cream-off" /></template>
