<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogq1sfe1k.css';
import '../../css/y/ylzgf4buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ogq1sfe1k"/><circle class="ylzgf4buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:location-on" /></template>
