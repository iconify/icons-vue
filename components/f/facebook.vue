<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2-tg4hoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":432};
const content = `<path class="v2-tg4hoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:facebook" /></template>
