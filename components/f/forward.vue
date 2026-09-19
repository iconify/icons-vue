<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgskp7_od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pgskp7_od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:forward" /></template>
