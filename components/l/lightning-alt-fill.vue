<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxojb-bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxojb-bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lightning-alt-fill" /></template>
