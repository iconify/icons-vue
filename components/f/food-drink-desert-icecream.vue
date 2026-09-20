<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyx_a2aii.css';
import '../../css/k/kqo6pkb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eyx_a2aii"/><path class="kqo6pkb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-desert-icecream" /></template>
