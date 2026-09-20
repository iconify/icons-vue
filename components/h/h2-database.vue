<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml7wh4fzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml7wh4fzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:h2-database" /></template>
