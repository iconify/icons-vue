<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuwzagbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yuwzagbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-2-add-o" /></template>
