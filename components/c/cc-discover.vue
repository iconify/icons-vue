<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r99c2sbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r99c2sbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-discover" /></template>
