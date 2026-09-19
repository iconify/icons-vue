<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udehd1bxt.css';
import '../../css/y/yancwabok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udehd1bxt"/><path class="yancwabok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:display" /></template>
