<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuy8ujbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuy8ujbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-alert-line" /></template>
