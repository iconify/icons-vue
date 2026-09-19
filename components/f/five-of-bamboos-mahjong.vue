<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sum2o0bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sum2o0bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:five-of-bamboos-mahjong" /></template>
