<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbez5bb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbez5bb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:laptop-camera-remix" /></template>
