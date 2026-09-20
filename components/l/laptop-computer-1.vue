<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-jv80k-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-jv80k-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:laptop-computer-1" /></template>
