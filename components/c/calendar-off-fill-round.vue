<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpcdrvr-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpcdrvr-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-fill-round" /></template>
