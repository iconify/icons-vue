<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mchzcjbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mchzcjbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:insert-cloud-video-remix" /></template>
