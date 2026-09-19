<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrvehib-t.css';
import '../../css/x/xm21wv__h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="rrvehib-t"/><path class="xm21wv__h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:esri-json-file" /></template>
