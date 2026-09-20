<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unrev1bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unrev1bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doco-cd-light" /></template>
