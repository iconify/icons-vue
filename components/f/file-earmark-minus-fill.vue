<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9jtd3mcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f9jtd3mcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-minus-fill" /></template>
