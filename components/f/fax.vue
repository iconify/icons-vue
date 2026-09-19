<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3i1l743g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q3i1l743g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:fax" /></template>
