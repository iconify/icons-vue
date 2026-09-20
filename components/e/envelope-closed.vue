<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t72jh4bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t72jh4bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:envelope-closed" /></template>
