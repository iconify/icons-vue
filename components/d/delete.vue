<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpfgoza3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="zpfgoza3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:delete" /></template>
