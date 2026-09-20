<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljd3w-lru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ljd3w-lru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:italic-solid" /></template>
