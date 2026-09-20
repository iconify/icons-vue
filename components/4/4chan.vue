<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo0ecjy4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo0ecjy4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:4chan" /></template>
