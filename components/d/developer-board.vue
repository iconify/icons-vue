<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itwu3q08m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="itwu3q08m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:developer-board" /></template>
