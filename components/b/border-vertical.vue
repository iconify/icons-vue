<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr23154xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr23154xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:border-vertical" /></template>
