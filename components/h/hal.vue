<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahlbw-byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahlbw-byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:hal" /></template>
