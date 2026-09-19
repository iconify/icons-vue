<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfiw6xiub.css';
import '../../css/o/oitaj0ijo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfiw6xiub"/><path class="oitaj0ijo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:condition-wait-point" /></template>
