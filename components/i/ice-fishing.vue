<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygne6q0py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ygne6q0py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:ice-fishing" /></template>
