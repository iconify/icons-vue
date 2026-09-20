<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcgy81our.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lcgy81our"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mail-archiver-dark" /></template>
