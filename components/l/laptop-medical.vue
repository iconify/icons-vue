<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2nxf_b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="t2nxf_b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:laptop-medical" /></template>
