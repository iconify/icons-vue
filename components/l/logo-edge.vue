<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai3xiq51b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ai3xiq51b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-edge" /></template>
