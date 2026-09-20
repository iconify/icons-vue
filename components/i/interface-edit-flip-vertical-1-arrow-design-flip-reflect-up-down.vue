<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/silnjob3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="silnjob3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-flip-vertical-1-arrow-design-flip-reflect-up-down" /></template>
