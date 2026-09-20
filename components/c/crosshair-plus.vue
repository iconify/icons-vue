<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9-x1ja6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9-x1ja6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:crosshair-plus" /></template>
