<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6g-z658n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l6g-z658n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aurral-light" /></template>
