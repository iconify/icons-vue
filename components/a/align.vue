<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epx26fbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epx26fbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:align" /></template>
