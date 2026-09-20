<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6_x9ibhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6_x9ibhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dashboard-circle-remix" /></template>
