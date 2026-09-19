<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0g4ab6vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o0g4ab6vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:flower" /></template>
