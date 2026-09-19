<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmf4qpbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mmf4qpbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:amex" /></template>
