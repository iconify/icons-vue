<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la_7fabio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="la_7fabio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frigoligo-dark" /></template>
