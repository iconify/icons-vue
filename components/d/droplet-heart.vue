<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdlbxko0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdlbxko0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:droplet-heart" /></template>
