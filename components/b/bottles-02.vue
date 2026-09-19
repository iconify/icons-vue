<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvrrshbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zvrrshbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bottles-02" /></template>
