<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb44q248l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gb44q248l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:battle-net" /></template>
