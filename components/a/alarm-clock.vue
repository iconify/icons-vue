<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rspl2bbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rspl2bbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-clock" /></template>
