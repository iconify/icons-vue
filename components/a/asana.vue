<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh-3yd6mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh-3yd6mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:asana" /></template>
