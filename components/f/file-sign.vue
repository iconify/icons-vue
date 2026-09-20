<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duj6xks4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duj6xks4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-sign" /></template>
