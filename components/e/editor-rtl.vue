<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knln1tbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="knln1tbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-rtl" /></template>
