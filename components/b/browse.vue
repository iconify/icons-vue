<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvs5jlb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="vvs5jlb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:browse" /></template>
