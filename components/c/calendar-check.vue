<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p69oc7ijo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="p69oc7ijo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:calendar-check" /></template>
