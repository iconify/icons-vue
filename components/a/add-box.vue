<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ral2q35-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ral2q35-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:add-box" /></template>
