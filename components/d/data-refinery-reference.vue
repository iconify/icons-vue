<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uez273bbq.css';
import '../../css/h/hhu-8gb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uez273bbq"/><path class="hhu-8gb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-refinery-reference" /></template>
