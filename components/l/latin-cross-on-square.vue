<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9jx6gj_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z9jx6gj_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:latin-cross-on-square" /></template>
