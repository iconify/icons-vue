<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp0p0ibwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gp0p0ibwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:folder-sign" /></template>
