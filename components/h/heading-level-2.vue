<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp2f6lb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="tp2f6lb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:heading-level-2" /></template>
