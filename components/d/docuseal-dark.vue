<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwy08i7pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwy08i7pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docuseal-dark" /></template>
