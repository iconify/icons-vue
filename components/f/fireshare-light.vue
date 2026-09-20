<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9b_qv0ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9b_qv0ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fireshare-light" /></template>
