<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqrwpqbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":416};
const content = `<path class="iqrwpqbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:case-check" /></template>
