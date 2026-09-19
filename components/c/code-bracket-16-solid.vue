<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcerrltoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xcerrltoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:code-bracket-16-solid" /></template>
