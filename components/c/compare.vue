<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9fdyfbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":480};
const content = `<path class="s9fdyfbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:compare" /></template>
