<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl_2il82l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl_2il82l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-line" /></template>
