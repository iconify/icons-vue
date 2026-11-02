<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u64e3ubte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u64e3ubte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-triangle-left-line" /></template>
