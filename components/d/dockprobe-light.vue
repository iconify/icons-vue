<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdrgw4bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdrgw4bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockprobe-light" /></template>
