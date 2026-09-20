<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viz9rp2hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="viz9rp2hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookstack-light" /></template>
