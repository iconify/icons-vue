<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3otsgbce.css';
import '../../css/k/kybyvbvqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i3otsgbce"/><circle class="kybyvbvqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:boolean" /></template>
