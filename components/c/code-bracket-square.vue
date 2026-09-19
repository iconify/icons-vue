<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy3skubph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vy3skubph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:code-bracket-square" /></template>
