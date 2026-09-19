<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo26xfwgu.css';
import '../../css/r/rokywmbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="xo26xfwgu"/><path class="rokywmbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:code-signing-service" /></template>
