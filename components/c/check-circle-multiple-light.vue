<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_pgq_bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q_pgq_bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:check-circle-multiple-light" /></template>
