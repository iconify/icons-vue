<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4v3gmdhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="t4v3gmdhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:calendar" /></template>
