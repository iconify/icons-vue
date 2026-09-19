<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9qqa1tma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="w9qqa1tma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:laptop-mac" /></template>
