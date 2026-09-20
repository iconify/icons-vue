<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwwggsb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwwggsb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:latex-light" /></template>
