<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2o8ylbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2o8ylbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dmm" /></template>
