<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf_h84bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hf_h84bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-and-tag" /></template>
