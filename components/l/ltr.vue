<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q51zqjkxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":12};
const content = `<path class="q51zqjkxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:ltr" /></template>
