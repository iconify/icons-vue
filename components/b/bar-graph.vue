<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w686qtbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w686qtbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bar-graph" /></template>
