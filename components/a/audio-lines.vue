<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw_yoi_9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw_yoi_9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:audio-lines" /></template>
