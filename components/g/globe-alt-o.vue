<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et6f67bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="et6f67bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-alt-o" /></template>
