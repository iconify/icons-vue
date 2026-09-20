<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_v651ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri_v651ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bewcloud-dark" /></template>
