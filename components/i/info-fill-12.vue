<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk0j2gbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xk0j2gbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:info-fill-12" /></template>
