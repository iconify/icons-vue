<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyi47_3sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xyi47_3sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:audio-description" /></template>
