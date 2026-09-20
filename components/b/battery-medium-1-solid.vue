<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th06fvafu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="th06fvafu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-medium-1-solid" /></template>
