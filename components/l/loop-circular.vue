<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmp74nh4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dmp74nh4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:loop-circular" /></template>
