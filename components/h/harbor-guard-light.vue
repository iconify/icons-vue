<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfwshp_nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfwshp_nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-guard-light" /></template>
