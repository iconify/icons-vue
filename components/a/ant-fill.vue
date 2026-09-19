<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khjp1zboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="khjp1zboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ant-fill" /></template>
