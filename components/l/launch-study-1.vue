<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4wx7em1k.css';
import '../../css/a/a5g7susyd.css';
import '../../css/t/tsv069uoe.css';
import '../../css/w/weo7tpp0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="p4wx7em1k"/><path class="a5g7susyd"/><path class="tsv069uoe"/><path class="weo7tpp0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:launch-study-1" /></template>
