<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7yldg-yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7yldg-yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cocoapods" /></template>
