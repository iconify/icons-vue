<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs3rtmbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vs3rtmbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-bottom" /></template>
