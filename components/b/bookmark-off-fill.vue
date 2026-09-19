<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9vgrzxot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9vgrzxot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bookmark-off-fill" /></template>
