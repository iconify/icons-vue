<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_11nbcho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_11nbcho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ktm" /></template>
