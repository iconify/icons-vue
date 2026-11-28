<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7lommy2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7lommy2l primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hand-coins-duotone" /></template>
