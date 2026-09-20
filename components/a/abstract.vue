<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta6dmmbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta6dmmbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:abstract" /></template>
