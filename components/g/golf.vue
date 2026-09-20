<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9u8tbcym.css';
import '../../css/o/o_4vtebcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q9u8tbcym"/><path class="o_4vtebcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:golf" /></template>
