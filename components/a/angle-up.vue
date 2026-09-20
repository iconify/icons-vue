<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb337052r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb337052r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:angle-up" /></template>
