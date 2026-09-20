<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q82_asybb.css';
import '../../css/j/jz4z07ajo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q82_asybb"/><path class="jz4z07ajo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:drawer-upload-bold" /></template>
