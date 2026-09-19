<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdp7dm02j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qdp7dm02j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-landcover" /></template>
