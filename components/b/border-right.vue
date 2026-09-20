<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx6820b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx6820b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:border-right" /></template>
