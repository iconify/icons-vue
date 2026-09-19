<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxgeqx4oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="kxgeqx4oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:globe" /></template>
