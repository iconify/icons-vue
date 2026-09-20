<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmd2sgb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmd2sgb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-down-fill" /></template>
