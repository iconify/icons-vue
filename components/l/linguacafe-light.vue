<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjcq1f4bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kjcq1f4bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linguacafe-light" /></template>
