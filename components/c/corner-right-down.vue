<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8qgc2bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8qgc2bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-right-down" /></template>
