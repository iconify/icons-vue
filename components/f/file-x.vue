<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbu8ekbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mbu8ekbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:file-x" /></template>
