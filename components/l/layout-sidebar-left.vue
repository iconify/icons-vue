<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibu1jey3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibu1jey3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-sidebar-left" /></template>
