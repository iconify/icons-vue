<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6gj24ocb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6gj24ocb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:last-fm-dark" /></template>
