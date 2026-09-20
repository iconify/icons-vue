<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlc5fibpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlc5fibpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:apple" /></template>
