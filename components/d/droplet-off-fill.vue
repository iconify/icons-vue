<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7weevkfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7weevkfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:droplet-off-fill" /></template>
