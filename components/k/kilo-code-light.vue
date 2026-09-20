<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqv8b4b-y.css';
import '../../css/t/tnpb5gbvj.css';
import '../../css/y/yxni68tfc.css';
import '../../css/q/q5cgd9bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cqv8b4b-y"/><path class="tnpb5gbvj"/><path class="yxni68tfc"/><path class="q5cgd9bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kilo-code-light" /></template>
