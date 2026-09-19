<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbfv5kbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbfv5kbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:broken-bone" /></template>
