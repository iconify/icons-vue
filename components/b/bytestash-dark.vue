<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shx8lpdkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shx8lpdkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bytestash-dark" /></template>
