<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl3_1h40s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vl3_1h40s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:check-circle-solid" /></template>
