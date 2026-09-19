<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od4a2obcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od4a2obcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:baseball" /></template>
