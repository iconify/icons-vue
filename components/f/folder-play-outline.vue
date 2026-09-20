<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo9n6d2yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo9n6d2yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-play-outline" /></template>
