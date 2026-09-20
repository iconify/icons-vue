<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic9catbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic9catbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:github-face" /></template>
