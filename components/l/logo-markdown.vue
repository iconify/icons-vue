<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp2hn9c7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vp2hn9c7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-markdown" /></template>
