<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2p0rybqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2p0rybqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-sync-outline" /></template>
