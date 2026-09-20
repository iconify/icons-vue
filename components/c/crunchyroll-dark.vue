<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1bwmk63r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1bwmk63r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crunchyroll-dark" /></template>
