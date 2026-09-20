<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzu84bbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mzu84bbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:info-solid" /></template>
