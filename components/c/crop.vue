<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxl344bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxl344bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:crop" /></template>
