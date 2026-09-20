<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-tk-vgci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-tk-vgci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fasten-health-light" /></template>
