<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy380gv4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oy380gv4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-empty-2-solid" /></template>
