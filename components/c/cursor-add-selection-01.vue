<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp1zs-blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp1zs-blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-add-selection-01" /></template>
