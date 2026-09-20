<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2-9esben.css';
import '../../css/w/w04o84byj.css';
import '../../css/d/dwzrjlbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2-9esben"/><path class="w04o84byj"/><path class="dwzrjlbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:analytics-bars-3-d-bold" /></template>
