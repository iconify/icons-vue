<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbj6ibb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbj6ibb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:alarm-panel" /></template>
