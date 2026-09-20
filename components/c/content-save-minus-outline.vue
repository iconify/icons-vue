<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlz05eb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlz05eb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-minus-outline" /></template>
