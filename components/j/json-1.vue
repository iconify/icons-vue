<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4d2zigbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4d2zigbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:json-1" /></template>
