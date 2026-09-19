<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvwzhz6sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tvwzhz6sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:mail-open" /></template>
