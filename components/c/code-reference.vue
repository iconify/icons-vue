<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6sj14czw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6sj14czw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:code-reference" /></template>
