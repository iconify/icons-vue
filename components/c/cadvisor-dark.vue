<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj3qpibvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uj3qpibvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cadvisor-dark" /></template>
