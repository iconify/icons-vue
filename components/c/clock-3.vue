<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzfi-7-ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzfi-7-ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clock-3" /></template>
