<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye4_c9bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ye4_c9bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingthree" /></template>
