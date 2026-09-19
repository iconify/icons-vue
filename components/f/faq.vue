<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4_6p9oov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="u4_6p9oov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:faq" /></template>
