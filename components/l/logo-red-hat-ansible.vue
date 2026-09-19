<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn8mjogke.css';
import '../../css/m/mxv0-rl9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gn8mjogke"/><path class="mxv0-rl9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-red-hat-ansible" /></template>
