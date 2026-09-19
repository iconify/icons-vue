<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxgx5bc6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vxgx5bc6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:circle-duo" /></template>
