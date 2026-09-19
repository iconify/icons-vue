<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdzj_9epy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xdzj_9epy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:imba" /></template>
