<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-l7bpb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-l7bpb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:discord" /></template>
