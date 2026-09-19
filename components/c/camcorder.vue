<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb82w-bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="yb82w-bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:camcorder" /></template>
