<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv2lcubgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hv2lcubgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-cloud-done" /></template>
