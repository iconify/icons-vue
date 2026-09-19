<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgf0h5e8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="vgf0h5e8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:atari" /></template>
