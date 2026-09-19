<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx4yyckre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tx4yyckre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:build-queue-new" /></template>
