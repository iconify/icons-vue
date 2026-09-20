<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo10_8b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo10_8b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-edit-line" /></template>
