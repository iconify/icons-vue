<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdf_o1auv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fdf_o1auv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-badge-16-solid" /></template>
