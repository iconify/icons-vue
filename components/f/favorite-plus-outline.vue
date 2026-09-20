<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1f3r8b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1f3r8b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-plus-outline" /></template>
