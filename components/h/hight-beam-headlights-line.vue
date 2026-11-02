<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omv4uwkpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omv4uwkpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hight-beam-headlights-line" /></template>
