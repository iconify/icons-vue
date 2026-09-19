<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yejrxzajr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":416};
const content = `<path class="yejrxzajr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:github" /></template>
