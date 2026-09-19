<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkb1tcc5d.css';
import '../../css/k/k2n9vabow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pkb1tcc5d"/><path class="k2n9vabow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-preliminary" /></template>
