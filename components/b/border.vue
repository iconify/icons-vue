<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8vlk9bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="h8vlk9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:border" /></template>
