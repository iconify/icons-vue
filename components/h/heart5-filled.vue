<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ytt-b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_ytt-b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart5-filled" /></template>
