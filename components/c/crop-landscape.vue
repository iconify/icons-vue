<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w13w75bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="w13w75bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop-landscape" /></template>
