<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx1u8yb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tx1u8yb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:input-address" /></template>
