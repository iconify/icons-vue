<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2_50w-9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2_50w-9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-pointing-right" /></template>
