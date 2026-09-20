<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdw7n2bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdw7n2bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fish-shell" /></template>
