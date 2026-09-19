<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2-u81xmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s2-u81xmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:close" /></template>
