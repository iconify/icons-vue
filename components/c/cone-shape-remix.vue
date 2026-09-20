<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vscvyybmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vscvyybmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cone-shape-remix" /></template>
