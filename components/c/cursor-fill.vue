<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixtg6lbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixtg6lbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cursor-fill" /></template>
