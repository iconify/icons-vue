<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl1yud0ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="nl1yud0ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-contour" /></template>
