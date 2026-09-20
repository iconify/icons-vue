<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdri55zjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jdri55zjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:exclamation-point-on-square" /></template>
