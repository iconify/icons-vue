<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtpw16buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtpw16buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:engine-fill" /></template>
