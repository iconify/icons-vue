<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm8b7jchf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm8b7jchf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-play-outline" /></template>
