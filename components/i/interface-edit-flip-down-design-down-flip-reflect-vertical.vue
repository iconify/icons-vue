<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fga303buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fga303buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-flip-down-design-down-flip-reflect-vertical" /></template>
