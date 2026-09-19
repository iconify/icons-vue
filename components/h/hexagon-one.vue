<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx_4j-mjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gx_4j-mjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hexagon-one" /></template>
