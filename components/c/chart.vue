<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw8ytabjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="lw8ytabjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:chart" /></template>
