<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft06mxbzl.css';
import '../../css/d/dlzqyubkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft06mxbzl"/><path class="dlzqyubkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:accounting-calculator-1-bold" /></template>
