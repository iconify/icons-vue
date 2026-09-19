<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z51nb4bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z51nb4bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-z1-pro-4" /></template>
