<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijhemtb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijhemtb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplets-sharp" /></template>
