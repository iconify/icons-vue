<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_we9ubre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_we9ubre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:help-circle-solid" /></template>
