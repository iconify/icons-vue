<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzd5abbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lzd5abbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:greater-than-equal" /></template>
