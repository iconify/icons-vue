<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mssa0nb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="mssa0nb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:globe-alt" /></template>
