<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdr68o9hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vdr68o9hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-center-fill" /></template>
