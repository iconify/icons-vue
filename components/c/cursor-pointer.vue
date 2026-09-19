<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpna39plv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpna39plv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-pointer" /></template>
