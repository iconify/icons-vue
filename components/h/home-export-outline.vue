<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agkix7v6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agkix7v6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-export-outline" /></template>
