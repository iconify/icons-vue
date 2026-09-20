<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypy18_b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypy18_b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkboxes-marked" /></template>
