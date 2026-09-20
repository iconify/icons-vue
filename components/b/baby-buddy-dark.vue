<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrlt_pgpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrlt_pgpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:baby-buddy-dark" /></template>
