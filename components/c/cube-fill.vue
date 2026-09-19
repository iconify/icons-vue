<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruyq1qb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruyq1qb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:cube-fill" /></template>
