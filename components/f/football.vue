<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c274zs7rb.css';
import '../../css/m/mwlmtkbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c274zs7rb"/><path class="mwlmtkbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:football" /></template>
