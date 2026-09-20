<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv10l8h9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iv10l8h9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kumiho-dark" /></template>
