<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llbqr5bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="llbqr5bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:horizontal-rule" /></template>
