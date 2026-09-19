<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q79rvz6zn.css';
import '../../css/r/rv25bpjtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="q79rvz6zn"/><path class="rv25bpjtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:2hearts" /></template>
