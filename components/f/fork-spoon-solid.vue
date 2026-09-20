<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-eur9bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t-eur9bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fork-spoon-solid" /></template>
