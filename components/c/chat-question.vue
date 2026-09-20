<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w78029obm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w78029obm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-question" /></template>
