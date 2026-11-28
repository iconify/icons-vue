<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy_jpibab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy_jpibab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:box-open-x" /></template>
