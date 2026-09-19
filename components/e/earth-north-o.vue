<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onn0dvxpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="onn0dvxpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-north-o" /></template>
