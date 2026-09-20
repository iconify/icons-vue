<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0-41zb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0-41zb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:information-serif-box-outline" /></template>
