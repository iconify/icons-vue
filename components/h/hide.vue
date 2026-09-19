<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsh2l2blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xsh2l2blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:hide" /></template>
