<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-krrsbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-krrsbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cup-off" /></template>
