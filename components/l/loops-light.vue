<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv4xi2bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fv4xi2bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loops-light" /></template>
