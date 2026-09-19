<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhhe-8bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bhhe-8bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:color" /></template>
