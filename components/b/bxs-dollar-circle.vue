<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8utccnkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8utccnkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dollar-circle" /></template>
