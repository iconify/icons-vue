<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex8j4trvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ex8j4trvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:circle-righthalf-fill" /></template>
