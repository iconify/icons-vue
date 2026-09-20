<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcroc_0yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rcroc_0yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:fire-station-14" /></template>
