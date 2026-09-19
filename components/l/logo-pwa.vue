<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q330gzbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q330gzbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-pwa" /></template>
