<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiv10dbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiv10dbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-ceiling-square" /></template>
