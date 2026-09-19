<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef8a_j6zj.css';
import '../../css/r/rxpq2xbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ef8a_j6zj"/><path class="rxpq2xbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-processor" /></template>
