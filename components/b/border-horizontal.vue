<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hud2g9gnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hud2g9gnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:border-horizontal" /></template>
