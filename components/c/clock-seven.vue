<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k81cs34vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k81cs34vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:clock-seven" /></template>
