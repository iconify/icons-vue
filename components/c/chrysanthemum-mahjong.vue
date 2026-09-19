<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd7pb6bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dd7pb6bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:chrysanthemum-mahjong" /></template>
