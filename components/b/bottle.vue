<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4k3mwl1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="k4k3mwl1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bottle" /></template>
