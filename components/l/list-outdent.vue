<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6-ubnbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6-ubnbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:list-outdent" /></template>
