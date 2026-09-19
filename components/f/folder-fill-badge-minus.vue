<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afe3ybcfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="afe3ybcfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-fill-badge-minus" /></template>
