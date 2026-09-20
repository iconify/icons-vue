<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlx4qbcqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlx4qbcqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:desktop-mac-dashboard" /></template>
