<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt6fivdvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt6fivdvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-up-lg" /></template>
