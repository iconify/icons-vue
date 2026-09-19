<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf4lu5bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cf4lu5bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:flag-o" /></template>
