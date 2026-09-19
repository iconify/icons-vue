<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2wcqfbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="c2wcqfbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:capacitator" /></template>
