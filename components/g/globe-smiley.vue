<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sws1y7b5y.css';
import '../../css/a/a8-k6ckwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="sws1y7b5y"/><path class="a8-k6ckwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-smiley" /></template>
