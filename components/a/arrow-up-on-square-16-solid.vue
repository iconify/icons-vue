<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8htw_vfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n8htw_vfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-on-square-16-solid" /></template>
