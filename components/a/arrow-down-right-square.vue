<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zai_d5b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zai_d5b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-right-square" /></template>
