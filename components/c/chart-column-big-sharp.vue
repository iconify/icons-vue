<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu-7yvbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu-7yvbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column-big-sharp" /></template>
