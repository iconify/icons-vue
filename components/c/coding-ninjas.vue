<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te_gapbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te_gapbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coding-ninjas" /></template>
