<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yql7wlbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yql7wlbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:certimate-light" /></template>
