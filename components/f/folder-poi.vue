<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4_y_tr5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="e4_y_tr5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:folder-poi" /></template>
