<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntftfkbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ntftfkbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-left-8" /></template>
