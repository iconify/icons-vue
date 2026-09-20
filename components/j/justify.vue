<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz2pfdbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rz2pfdbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:justify" /></template>
