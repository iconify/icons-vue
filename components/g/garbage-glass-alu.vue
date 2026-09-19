<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcdf_tb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcdf_tb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:garbage-glass-alu" /></template>
