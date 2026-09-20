<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv1ourhyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dv1ourhyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ipvanish-dark" /></template>
