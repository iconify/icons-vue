<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-kbcn09w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="f-kbcn09w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:b-upper-case" /></template>
