<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pghlwtbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pghlwtbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floppy-disc-cog-outline" /></template>
