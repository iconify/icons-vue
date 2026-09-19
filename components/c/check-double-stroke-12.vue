<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw46o2y3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hw46o2y3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-double-stroke-12" /></template>
