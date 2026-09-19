<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv90u3bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nv90u3bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:brightness" /></template>
