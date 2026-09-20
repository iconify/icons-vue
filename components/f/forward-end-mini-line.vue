<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlszn25vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlszn25vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-end-mini-line" /></template>
