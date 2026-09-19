<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgd-exbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":999,"height":1000};
const content = `<path class="jgd-exbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-squint" /></template>
