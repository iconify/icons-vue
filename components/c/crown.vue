<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gau26bbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gau26bbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:crown" /></template>
