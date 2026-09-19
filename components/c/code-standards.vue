<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca5ull6cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ca5ull6cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:code-standards" /></template>
