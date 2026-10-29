<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-be4tb1z.css';
import '../../css/f/fijx44bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-be4tb1z wm-k"/><path class="fijx44bhr wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-down-right" /></template>
