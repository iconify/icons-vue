<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnij756ni.css';
import '../../css/s/sz1mxmeui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jnij756ni"/><path class="sz1mxmeui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:breaking-change" /></template>
