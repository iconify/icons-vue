<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjcgg0b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjcgg0b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:app-window-gear" /></template>
