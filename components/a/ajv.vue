<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onquh7bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onquh7bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ajv" /></template>
