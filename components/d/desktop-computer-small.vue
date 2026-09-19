<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtw1_oswe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dtw1_oswe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:desktop-computer-small" /></template>
