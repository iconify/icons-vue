<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_lg19ylu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_lg19ylu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:icons8" /></template>
