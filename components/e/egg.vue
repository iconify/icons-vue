<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl7biob5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl7biob5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:egg" /></template>
