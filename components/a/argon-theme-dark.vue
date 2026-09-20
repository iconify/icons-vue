<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1ocinb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1ocinb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:argon-theme-dark" /></template>
