<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifspalbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ifspalbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-asia" /></template>
