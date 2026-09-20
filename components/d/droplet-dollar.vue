<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqc0fgbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqc0fgbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-dollar" /></template>
