<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wegkc6b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wegkc6b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:grain" /></template>
