<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh7r9_dwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh7r9_dwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:airplane" /></template>
