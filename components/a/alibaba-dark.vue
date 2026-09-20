<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvc-bxpqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yvc-bxpqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alibaba-dark" /></template>
