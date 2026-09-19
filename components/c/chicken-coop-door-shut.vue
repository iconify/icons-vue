<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed5q7mbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed5q7mbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chicken-coop-door-shut" /></template>
