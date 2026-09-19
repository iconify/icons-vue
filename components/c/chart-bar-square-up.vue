<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhng6tn2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhng6tn2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-square-up" /></template>
