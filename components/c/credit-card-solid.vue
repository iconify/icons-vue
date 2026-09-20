<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5__nsf_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m5__nsf_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:credit-card-solid" /></template>
