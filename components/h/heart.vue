<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgj96cc_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":710,"height":780};
const content = `<path class="kgj96cc_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:heart" /></template>
