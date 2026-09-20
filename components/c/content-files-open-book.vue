<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m20rxt8mc.css';
import '../../css/p/pkcnx6ceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m20rxt8mc"/><path class="pkcnx6ceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-open-book" /></template>
