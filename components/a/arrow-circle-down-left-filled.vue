<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzhmhbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czzhmhbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-down-left-filled" /></template>
