<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grwne1bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<circle class="grwne1bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:circle" /></template>
