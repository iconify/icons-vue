<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu42zbd3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yu42zbd3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aeterna-light" /></template>
