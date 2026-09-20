<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rufm80bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rufm80bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-flip-vertical-2-arrow-design-flip-reflect-up-down" /></template>
