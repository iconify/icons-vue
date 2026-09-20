<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t41hpxb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t41hpxb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jsdelivr" /></template>
