<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmtd3vrky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmtd3vrky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lasso-round" /></template>
