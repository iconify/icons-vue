<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsb95tbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsb95tbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dstv" /></template>
