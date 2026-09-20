<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn1nhjbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn1nhjbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:cursor-highlight-click-1" /></template>
