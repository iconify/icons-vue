<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yab8gogpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yab8gogpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:grass" /></template>
