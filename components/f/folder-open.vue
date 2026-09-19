<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5m2b65fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y5m2b65fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:folder-open" /></template>
