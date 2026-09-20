<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofvt09bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ofvt09bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:license" /></template>
