<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je5g7erlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je5g7erlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:list-task" /></template>
