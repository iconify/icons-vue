<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlg5nbb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xlg5nbb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apc-light" /></template>
