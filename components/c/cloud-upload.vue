<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4oh4_byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="s4oh4_byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud-upload" /></template>
