<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrxv_pbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wrxv_pbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:code" /></template>
