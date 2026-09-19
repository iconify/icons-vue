<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7n05ph0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="k7n05ph0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:famale" /></template>
