<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su2ludbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su2ludbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:firebase" /></template>
