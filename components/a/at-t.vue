<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxt9wpbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxt9wpbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:at-t" /></template>
