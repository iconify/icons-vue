<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoyi67mez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoyi67mez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-top-left" /></template>
