<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3hvzhb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p3hvzhb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:cut" /></template>
