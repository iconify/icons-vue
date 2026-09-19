<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v116ycm1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v116ycm1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-circle" /></template>
