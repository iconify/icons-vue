<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqb-pdbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aqb-pdbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:eye-off-solid" /></template>
