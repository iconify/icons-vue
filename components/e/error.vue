<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdi7wib5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="qdi7wib5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:error" /></template>
