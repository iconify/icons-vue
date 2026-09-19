<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upv8a5aru.css';
import '../../css/y/y67djbpgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="upv8a5aru"/><path class="y67djbpgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location" /></template>
