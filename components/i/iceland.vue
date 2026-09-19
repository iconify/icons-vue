<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etw1sjxsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etw1sjxsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:iceland" /></template>
