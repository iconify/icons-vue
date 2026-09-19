<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcy2s53wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zcy2s53wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-compact-down" /></template>
