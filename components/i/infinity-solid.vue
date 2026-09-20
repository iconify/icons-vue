<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrlf1oakz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yrlf1oakz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:infinity-solid" /></template>
