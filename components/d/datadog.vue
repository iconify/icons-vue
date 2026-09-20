<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjm6t_b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":274};
const content = `<path clip-rule="evenodd" class="tjm6t_b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:datadog" /></template>
