<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6g75oclj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6g75oclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:layout-list" /></template>
