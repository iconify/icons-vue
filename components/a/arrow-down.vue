<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkbkpbc4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="rkbkpbc4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:arrow-down" /></template>
