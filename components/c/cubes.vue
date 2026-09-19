<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh-v3mdgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2176,"height":1792};
const content = `<path class="uh-v3mdgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cubes" /></template>
