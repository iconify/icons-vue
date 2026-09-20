<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuihi2b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yuihi2b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:business-time" /></template>
