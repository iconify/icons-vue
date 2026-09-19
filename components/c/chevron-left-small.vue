<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppf2-26kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ppf2-26kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-left-small" /></template>
