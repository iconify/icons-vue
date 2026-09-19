<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcism4bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcism4bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:json5" /></template>
