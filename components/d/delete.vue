<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgdtsgbcc.css';
import '../../css/v/vj4rr6bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fgdtsgbcc"/><path class="vj4rr6bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:delete" /></template>
