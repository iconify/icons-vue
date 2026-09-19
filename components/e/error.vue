<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc7afxbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc7afxbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:error" /></template>
