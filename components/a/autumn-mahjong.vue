<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryner9xzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ryner9xzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:autumn-mahjong" /></template>
