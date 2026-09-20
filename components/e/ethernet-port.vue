<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph3u7ibzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ph3u7ibzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ethernet-port" /></template>
