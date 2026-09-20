<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joi84pfdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joi84pfdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cpu-line" /></template>
