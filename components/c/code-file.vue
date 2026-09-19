<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt2awjbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tt2awjbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:code-file" /></template>
