<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlm3xgzsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlm3xgzsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:git-commit-vertical" /></template>
