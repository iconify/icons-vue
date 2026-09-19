<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9cdyobop.css';
import '../../css/g/gzydm7bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v9cdyobop"/><path class="gzydm7bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:angle" /></template>
