<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex9iwebhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ex9iwebhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calls" /></template>
