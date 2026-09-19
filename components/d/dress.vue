<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czbq_4byq.css';
import '../../css/w/wq7voubuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="czbq_4byq"/><path class="wq7voubuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:dress" /></template>
