<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-6ltbboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-6ltbboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kanidm-dark" /></template>
