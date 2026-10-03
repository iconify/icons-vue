<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6ankxbmd.css';
import '../../css/w/w951xmbwv.css';
import '../../css/e/ez4l1crno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y6ankxbmd"/><path class="w951xmbwv"/><path class="ez4l1crno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headplane" /></template>
