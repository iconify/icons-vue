<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8eln41js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8eln41js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:libreofficecalc" /></template>
