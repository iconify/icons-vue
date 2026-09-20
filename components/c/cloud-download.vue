<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb3yl8b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="zb3yl8b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:cloud-download" /></template>
