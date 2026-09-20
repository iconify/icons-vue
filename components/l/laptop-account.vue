<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmhj1ffwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmhj1ffwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:laptop-account" /></template>
