<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eplhw_nba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eplhw_nba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:glass2" /></template>
