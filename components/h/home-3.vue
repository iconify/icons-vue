<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c50pgwbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c50pgwbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:home-3" /></template>
