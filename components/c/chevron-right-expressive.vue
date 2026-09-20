<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdt2dg_fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdt2dg_fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:chevron-right-expressive" /></template>
