<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmy1u9bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qmy1u9bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hand-point-left" /></template>
