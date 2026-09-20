<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk8o7xbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk8o7xbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-off-fill" /></template>
