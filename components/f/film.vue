<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa17g_wlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="wa17g_wlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:film" /></template>
