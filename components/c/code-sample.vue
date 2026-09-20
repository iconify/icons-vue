<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-s4vtjqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":14};
const content = `<path class="n-s4vtjqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:code-sample" /></template>
