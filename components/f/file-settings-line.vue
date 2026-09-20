<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxwnwub6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxwnwub6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-settings-line" /></template>
