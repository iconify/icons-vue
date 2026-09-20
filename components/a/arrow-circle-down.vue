<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcddw3bvx.css';
import '../../css/i/i3a4j3hes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcddw3bvx"/><path class="i3a4j3hes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:arrow-circle-down" /></template>
