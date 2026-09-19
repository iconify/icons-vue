<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti-pj-x_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ti-pj-x_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hdr" /></template>
