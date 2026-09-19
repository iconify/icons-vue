<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx3cpnbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":760,"height":800};
const content = `<path class="cx3cpnbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:github" /></template>
