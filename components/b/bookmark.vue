<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h36y6dxnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h36y6dxnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:bookmark" /></template>
