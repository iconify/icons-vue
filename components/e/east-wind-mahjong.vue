<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sffbs1avt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sffbs1avt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:east-wind-mahjong" /></template>
