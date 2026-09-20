<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk7w8lbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk7w8lbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:circle-layer" /></template>
