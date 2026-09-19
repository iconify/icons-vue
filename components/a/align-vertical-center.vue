<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iavtan26b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iavtan26b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:align-vertical-center" /></template>
