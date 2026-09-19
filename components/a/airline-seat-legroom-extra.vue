<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl_3d6bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":384};
const content = `<path class="xl_3d6bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airline-seat-legroom-extra" /></template>
