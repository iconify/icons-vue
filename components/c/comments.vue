<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4sxp5bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="t4sxp5bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:comments" /></template>
