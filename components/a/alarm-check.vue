<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu5immt_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="yu5immt_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alarm-check" /></template>
