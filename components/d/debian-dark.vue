<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4kkt5bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w4kkt5bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:debian-dark" /></template>
