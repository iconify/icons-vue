<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi7958byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gi7958byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:api-blueprint" /></template>
