<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okr4k8bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okr4k8bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-diamond" /></template>
