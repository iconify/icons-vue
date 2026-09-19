<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbl37cbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nbl37cbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ambulance" /></template>
