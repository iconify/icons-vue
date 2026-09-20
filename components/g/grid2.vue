<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwbxz27sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwbxz27sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid2" /></template>
