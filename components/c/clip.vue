<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nggtlqu-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":718,"height":701};
const content = `<path class="nggtlqu-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:clip" /></template>
