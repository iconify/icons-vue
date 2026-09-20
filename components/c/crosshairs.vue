<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy2o1zb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jy2o1zb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:crosshairs" /></template>
