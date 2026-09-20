<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isc-7v3rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="isc-7v3rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:guidepost" /></template>
