<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf72p_bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vf72p_bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:choices" /></template>
