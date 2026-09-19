<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq1w6hbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq1w6hbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:glasses-alt-filled" /></template>
