<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olajivb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="olajivb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:family" /></template>
