<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh6krl1fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oh6krl1fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:emoji-2" /></template>
