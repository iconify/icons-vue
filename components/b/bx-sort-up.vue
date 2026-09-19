<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvag3mweo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvag3mweo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-sort-up" /></template>
