<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urrv_ccnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urrv_ccnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:files" /></template>
