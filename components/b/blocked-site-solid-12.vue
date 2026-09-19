<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyjp6ob9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lyjp6ob9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:blocked-site-solid-12" /></template>
