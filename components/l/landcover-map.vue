<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec0legbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ec0legbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:landcover-map" /></template>
