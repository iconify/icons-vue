<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joa-7ibra.css';
import '../../css/p/pgshgrb4e.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 joa-7ibra"/><path class="clr-i-outline clr-i-outline-path-2 pgshgrb4e"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:copy-line" /></template>
