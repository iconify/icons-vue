<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3-lr-62j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3-lr-62j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-plus" /></template>
