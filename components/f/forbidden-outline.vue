<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc5mlowhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dc5mlowhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forbidden-outline" /></template>
