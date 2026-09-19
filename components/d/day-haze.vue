<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8iec2qwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="v8iec2qwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:day-haze" /></template>
