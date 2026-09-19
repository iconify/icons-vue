<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n41w4lshj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n41w4lshj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:low-vision" /></template>
