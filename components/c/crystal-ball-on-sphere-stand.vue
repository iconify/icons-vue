<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmiw9pf2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dmiw9pf2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crystal-ball-on-sphere-stand" /></template>
