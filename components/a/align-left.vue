<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv30okbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uv30okbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:align-left" /></template>
