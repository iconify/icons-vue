<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s73u1rbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s73u1rbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:9router-dark" /></template>
