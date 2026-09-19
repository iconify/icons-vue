<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ara8lji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i_ara8lji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:gg-circle" /></template>
