<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdzraxb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdzraxb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-heart-multiple-outline" /></template>
