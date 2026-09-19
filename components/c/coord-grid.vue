<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g57i3fc6z.css';
import '../../css/e/eedc6fbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g57i3fc6z"/><path class="eedc6fbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:coord-grid" /></template>
