<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxx-bo3lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxx-bo3lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:laragon" /></template>
