<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn-bxyb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vn-bxyb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:golang-light" /></template>
