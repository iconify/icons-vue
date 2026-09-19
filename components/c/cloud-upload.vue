<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg40_p8ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kg40_p8ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:cloud-upload" /></template>
