<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saq9jgb9j.css';
import '../../css/q/qyfnmsb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="saq9jgb9j"/><path class="qyfnmsb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:drinking-water-15" /></template>
