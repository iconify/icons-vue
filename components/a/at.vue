<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8etgtbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="o8etgtbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:at" /></template>
