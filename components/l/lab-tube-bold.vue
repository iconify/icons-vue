<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1n_cvbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1n_cvbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:lab-tube-bold" /></template>
