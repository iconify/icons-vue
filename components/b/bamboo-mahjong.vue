<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsmpazbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wsmpazbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bamboo-mahjong" /></template>
