<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fay30qbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="fay30qbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bluetooth-b" /></template>
