<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl_omuber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl_omuber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clock3-filled" /></template>
