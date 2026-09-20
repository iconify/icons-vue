<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzvb8wm7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mzvb8wm7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:crop-alt-solid" /></template>
