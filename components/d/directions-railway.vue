<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peb9bwbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="peb9bwbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:directions-railway" /></template>
