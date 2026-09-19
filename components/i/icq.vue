<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1un75b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1un75b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:icq" /></template>
