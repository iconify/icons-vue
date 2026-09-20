<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpvdj9byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpvdj9byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-scale-dark" /></template>
