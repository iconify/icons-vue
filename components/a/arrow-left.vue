<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gipn88bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gipn88bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-left" /></template>
