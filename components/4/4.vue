<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzdk69b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lzdk69b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:4" /></template>
