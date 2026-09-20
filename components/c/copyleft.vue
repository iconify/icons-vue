<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg1d49btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1d49btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:copyleft" /></template>
