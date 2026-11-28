<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylzad086p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylzad086p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folders-x" /></template>
