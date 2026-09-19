<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz7s1z9sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wz7s1z9sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cursor" /></template>
