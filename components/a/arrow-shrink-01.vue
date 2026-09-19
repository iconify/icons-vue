<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drs_rw39z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drs_rw39z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-shrink-01" /></template>
