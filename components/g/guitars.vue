<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed7v4lbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ed7v4lbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:guitars" /></template>
