<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiw02y_uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiw02y_uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-z" /></template>
