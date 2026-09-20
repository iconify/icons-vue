<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxz09hbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxz09hbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowdstrike-dark" /></template>
