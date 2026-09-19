<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9g07hbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z9g07hbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:fox-face" /></template>
