<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kso_zevhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kso_zevhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-16-solid" /></template>
