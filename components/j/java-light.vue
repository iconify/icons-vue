<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if5jybchv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="if5jybchv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:java-light" /></template>
