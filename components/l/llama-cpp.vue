<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5e2uw75d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5e2uw75d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:llama-cpp" /></template>
