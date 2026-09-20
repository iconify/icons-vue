<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbuaxzl0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbuaxzl0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-robot-confused-outline" /></template>
