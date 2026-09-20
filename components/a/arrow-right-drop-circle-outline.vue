<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdhnu-7by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdhnu-7by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-drop-circle-outline" /></template>
