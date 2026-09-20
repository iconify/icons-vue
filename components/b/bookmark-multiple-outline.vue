<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msid8bbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msid8bbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-multiple-outline" /></template>
