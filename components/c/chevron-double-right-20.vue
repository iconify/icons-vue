<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amszec7ov.css';
import '../../css/r/roxo8uutm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="amszec7ov"/><path class="roxo8uutm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-right-20" /></template>
