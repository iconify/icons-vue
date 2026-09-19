<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8fzehbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="j8fzehbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:h-square" /></template>
