<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxwh64lzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lxwh64lzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:code-bracket-square-20-solid" /></template>
