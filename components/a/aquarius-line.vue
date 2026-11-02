<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl1it1boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl1it1boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aquarius-line" /></template>
