<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr8fltb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr8fltb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:id-card-lock" /></template>
