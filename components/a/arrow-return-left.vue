<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q00d-m2wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q00d-m2wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-return-left" /></template>
