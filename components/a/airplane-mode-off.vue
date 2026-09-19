<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmj35zbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmj35zbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:airplane-mode-off" /></template>
