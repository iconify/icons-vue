<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4nn2vsvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4nn2vsvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:charging-battery-empty" /></template>
