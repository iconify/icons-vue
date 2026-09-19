<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv47u9sdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="gv47u9sdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:full-screen" /></template>
