<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldhnb-but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ldhnb-but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:code-bracket-square-16-solid" /></template>
