<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvbvjfbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvbvjfbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:edit-copy" /></template>
