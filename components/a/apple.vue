<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs_6xacfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rs_6xacfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple" /></template>
