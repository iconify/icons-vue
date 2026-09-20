<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h27efgb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h27efgb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:greensock" /></template>
