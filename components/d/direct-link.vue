<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxv_pcivz.css';
import '../../css/c/clqjdubcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qxv_pcivz"/><path class="clqjdubcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direct-link" /></template>
