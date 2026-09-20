<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw379qbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hw379qbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:flight" /></template>
