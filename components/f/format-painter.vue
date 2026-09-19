<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j16d4ujcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j16d4ujcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:format-painter" /></template>
