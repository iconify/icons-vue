<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou3oexjod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ou3oexjod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:invisible-2-remix" /></template>
