<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xju7dznge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xju7dznge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:astroid" /></template>
