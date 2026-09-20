<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh_n6absf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yh_n6absf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flood-light" /></template>
