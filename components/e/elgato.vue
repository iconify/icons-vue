<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezq9uabrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezq9uabrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:elgato" /></template>
