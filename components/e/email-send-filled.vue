<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgk54msjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wgk54msjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:email-send-filled" /></template>
