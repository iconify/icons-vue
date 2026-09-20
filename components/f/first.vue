<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlnah18dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlnah18dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:first" /></template>
