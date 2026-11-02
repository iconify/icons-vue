<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt83grb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt83grb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawer-2-line" /></template>
