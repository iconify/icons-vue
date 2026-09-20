<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3jx_2bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3jx_2bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mail-archiver-light" /></template>
