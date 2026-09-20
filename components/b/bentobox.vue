<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbqqu2bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbqqu2bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bentobox" /></template>
