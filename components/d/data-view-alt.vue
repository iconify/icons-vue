<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgmhddevn.css';
import '../../css/p/pw47icbmy.css';
import '../../css/c/cb4hdplqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="lgmhddevn"/><path class="pw47icbmy"/><path class="cb4hdplqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-view-alt" /></template>
