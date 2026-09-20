<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd5rqgb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yd5rqgb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garage-light" /></template>
