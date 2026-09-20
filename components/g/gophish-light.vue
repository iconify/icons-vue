<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3r9d2zij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i3r9d2zij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gophish-light" /></template>
