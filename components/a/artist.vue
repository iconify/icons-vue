<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r42o0bbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r42o0bbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:artist" /></template>
