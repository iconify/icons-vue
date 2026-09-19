<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5waivb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j5waivb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:down-arrow" /></template>
