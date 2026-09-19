<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmum8ru3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmum8ru3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-check" /></template>
