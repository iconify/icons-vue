<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtyy-2w-p.css';
import '../../css/q/qds-v0bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtyy-2w-p"/><path class="qds-v0bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-remove" /></template>
