<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c89gs2bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c89gs2bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:incomplete" /></template>
