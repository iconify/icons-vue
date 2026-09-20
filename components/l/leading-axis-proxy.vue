<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv6_a4bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pv6_a4bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:leading-axis-proxy" /></template>
