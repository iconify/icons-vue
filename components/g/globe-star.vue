<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn5-me7co.css';
import '../../css/x/xpeiq2kly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zn5-me7co"/><path class="xpeiq2kly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-star" /></template>
