<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju2o_hbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju2o_hbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:magnifying-glass-circle" /></template>
