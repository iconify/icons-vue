<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr4e52byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr4e52byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:antenna-bars-2" /></template>
