<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfbdei4yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yfbdei4yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hierarchy-10" /></template>
