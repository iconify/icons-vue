<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thk8cdcdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thk8cdcdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:home-info" /></template>
