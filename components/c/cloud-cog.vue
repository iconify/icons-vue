<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u37qm4b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u37qm4b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-cog" /></template>
