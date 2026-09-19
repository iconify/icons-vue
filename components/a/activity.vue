<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1imygbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n1imygbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:activity" /></template>
