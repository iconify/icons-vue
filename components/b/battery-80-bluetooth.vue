<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsyu9yx7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsyu9yx7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-80-bluetooth" /></template>
