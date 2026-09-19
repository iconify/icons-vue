<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ci2_etv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d_ci2_etv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lock-open-16-solid" /></template>
