<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k00a4g7yc.css';
import '../../css/o/otjvghwvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k00a4g7yc"/><path class="otjvghwvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:application-virtual" /></template>
