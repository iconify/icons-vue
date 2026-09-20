<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d69grsp_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d69grsp_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:internet-archive-light" /></template>
