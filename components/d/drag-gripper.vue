<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir_fjwbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ir_fjwbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:drag-gripper" /></template>
