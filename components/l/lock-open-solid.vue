<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_-ave30o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r_-ave30o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:lock-open-solid" /></template>
