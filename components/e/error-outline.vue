<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaecykbpq.css';
import '../../css/c/cpwp98h5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jaecykbpq"/><path class="cpwp98h5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:error-outline" /></template>
