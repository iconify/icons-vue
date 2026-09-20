<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crs8b8bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crs8b8bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bulldozer" /></template>
