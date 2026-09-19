<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxz2ub4zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fxz2ub4zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:delicious" /></template>
