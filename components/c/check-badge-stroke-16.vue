<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txh_v0bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="txh_v0bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-badge-stroke-16" /></template>
