<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxkp-qqyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxkp-qqyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-square2-filled" /></template>
