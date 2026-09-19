<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzn-3lsgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yzn-3lsgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:greaterthan-square-fill" /></template>
