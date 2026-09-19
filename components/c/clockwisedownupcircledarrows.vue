<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu9emeb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bu9emeb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:clockwisedownupcircledarrows" /></template>
