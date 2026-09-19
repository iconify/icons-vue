<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm83ibnhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="rm83ibnhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:check-circle" /></template>
