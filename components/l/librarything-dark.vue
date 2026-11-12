<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx8r0fbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lx8r0fbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librarything-dark" /></template>
