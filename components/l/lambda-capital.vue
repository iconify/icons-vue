<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phu1nbjot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phu1nbjot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:lambda-capital" /></template>
