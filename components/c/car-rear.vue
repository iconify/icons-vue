<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx40v78ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rx40v78ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:car-rear" /></template>
