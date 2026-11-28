<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz4u5db2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz4u5db2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-circle-left" /></template>
