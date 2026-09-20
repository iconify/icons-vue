<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crszc-qch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crszc-qch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bookmyshow" /></template>
