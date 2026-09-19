<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usifnk4ig.css';
import '../../css/b/bv734nb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="usifnk4ig"/><path class="bv734nb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-privileged-access-gateway" /></template>
