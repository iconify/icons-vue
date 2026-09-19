<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcpny1buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rcpny1buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:application" /></template>
