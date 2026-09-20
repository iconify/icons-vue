<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl83o0buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl83o0buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arachnid-thread" /></template>
