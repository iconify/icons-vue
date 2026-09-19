<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnv8y4ccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="hnv8y4ccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:circle-o" /></template>
