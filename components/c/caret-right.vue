<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0xtwtpgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j0xtwtpgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:caret-right" /></template>
