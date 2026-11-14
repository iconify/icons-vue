<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nylo2vbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nylo2vbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haproxy-dark" /></template>
