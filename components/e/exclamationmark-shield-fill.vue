<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fllm-o0kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fllm-o0kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:exclamationmark-shield-fill" /></template>
