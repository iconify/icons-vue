<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd4ogl5wu.css';
import '../../css/o/oqzccw9bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="qd4ogl5wu"/><path class="oqzccw9bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logical-partition" /></template>
