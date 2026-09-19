<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9b1o0b9t.css';
import '../../css/m/mcwbb7b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="w9b1o0b9t"/><path class="mcwbb7b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:instance-virtual" /></template>
