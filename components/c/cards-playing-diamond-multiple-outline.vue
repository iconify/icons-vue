<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy2pjbcso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy2pjbcso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-diamond-multiple-outline" /></template>
