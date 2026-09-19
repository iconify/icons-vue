<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh_m7bbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vh_m7bbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:hand-thumb-down" /></template>
