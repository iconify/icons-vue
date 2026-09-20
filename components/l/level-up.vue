<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duccjbc7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="duccjbc7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:level-up" /></template>
