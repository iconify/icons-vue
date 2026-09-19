<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvdbppbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xvdbppbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:greaterthan" /></template>
