<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj-mhdcsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lj-mhdcsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:greaterthan-circle" /></template>
