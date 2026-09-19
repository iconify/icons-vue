<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwv_0dxhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xwv_0dxhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dodo" /></template>
