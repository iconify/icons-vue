<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvu-llngc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="jvu-llngc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:contract" /></template>
