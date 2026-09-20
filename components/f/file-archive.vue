<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfd8-93rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tfd8-93rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-archive" /></template>
