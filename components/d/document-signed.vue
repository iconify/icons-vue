<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqhh-5byr.css';
import '../../css/x/xo26xfwgu.css';
import '../../css/p/pa6q0ccyu.css';
import '../../css/y/yefmyk4qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xqhh-5byr"/><circle class="xo26xfwgu"/><path class="pa6q0ccyu"/><path class="yefmyk4qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-signed" /></template>
