<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reo7q0byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reo7q0byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:firefox" /></template>
