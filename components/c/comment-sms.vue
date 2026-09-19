<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd6z99bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yd6z99bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:comment-sms" /></template>
