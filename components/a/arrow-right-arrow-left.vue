<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4ohkvbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q4ohkvbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right-arrow-left" /></template>
