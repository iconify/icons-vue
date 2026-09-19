<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw73jobqx.css';
import '../../css/r/ra2lh9qeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yw73jobqx"/><path class="ra2lh9qeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-react" /></template>
