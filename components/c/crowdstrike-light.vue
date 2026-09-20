<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn5ajfbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dn5ajfbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowdstrike-light" /></template>
