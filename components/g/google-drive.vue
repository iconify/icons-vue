<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj62g-b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":408};
const content = `<path class="oj62g-b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google-drive" /></template>
