<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxq1d5bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sxq1d5bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:five-of-bamboos-mahjong-filled" /></template>
