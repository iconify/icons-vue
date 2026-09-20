<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx_19xfxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="nx_19xfxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:buttons" /></template>
