<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy1ef0rgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uy1ef0rgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:construction-hammer" /></template>
