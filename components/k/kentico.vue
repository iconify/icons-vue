<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qco8pwbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qco8pwbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kentico" /></template>
