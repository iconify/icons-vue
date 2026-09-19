<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0nz5z_0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="r0nz5z_0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:functions" /></template>
