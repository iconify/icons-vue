<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpm9sb8kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mpm9sb8kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ellipsis" /></template>
