<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzr4-wmbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wzr4-wmbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iheartradio-light" /></template>
