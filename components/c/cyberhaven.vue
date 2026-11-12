<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in33yub4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in33yub4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cyberhaven" /></template>
