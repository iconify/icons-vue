<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc-xrjy4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jc-xrjy4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:clockify" /></template>
