<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzt-7wzoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qzt-7wzoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:compare" /></template>
