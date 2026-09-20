<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wugs8pltu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wugs8pltu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hetzner-dark" /></template>
